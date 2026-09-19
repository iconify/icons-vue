<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hbn71sjeo.css';
import '../../css/z/zai84lbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="link-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="hbn71sjeo"/><path class="zai84lbsw"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:link-outline" /></template>
