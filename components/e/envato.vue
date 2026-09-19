<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s50rjobvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="s50rjobvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:envato" /></template>
