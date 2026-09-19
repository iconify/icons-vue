<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riwpk_voa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="riwpk_voa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:jekyll" /></template>
