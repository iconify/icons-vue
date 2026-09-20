<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5d9x7bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5d9x7bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:itchdotio" /></template>
