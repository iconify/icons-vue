<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbww4uc3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fbww4uc3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:keyboard-outline" /></template>
