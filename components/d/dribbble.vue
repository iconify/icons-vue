<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2x79mbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a2x79mbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:dribbble" /></template>
