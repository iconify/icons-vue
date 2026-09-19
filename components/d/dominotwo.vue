<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywv-5vb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="ywv-5vb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominotwo" /></template>
