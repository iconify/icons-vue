<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g83i4kb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="g83i4kb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hexo" /></template>
