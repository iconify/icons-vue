<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf4c-9c0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="zf4c-9c0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominothree" /></template>
