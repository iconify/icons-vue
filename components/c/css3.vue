<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yopy-3xrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="yopy-3xrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:css3" /></template>
