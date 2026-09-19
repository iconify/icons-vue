<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uucn2tb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="uucn2tb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:creative-commons-nd" /></template>
