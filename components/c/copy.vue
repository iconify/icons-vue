<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v51606bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="v51606bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:copy" /></template>
