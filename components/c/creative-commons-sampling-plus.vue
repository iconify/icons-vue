<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjtk3-bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="wjtk3-bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:creative-commons-sampling-plus" /></template>
