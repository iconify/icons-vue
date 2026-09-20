<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt-7dbckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt-7dbckp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:babelio" /></template>
