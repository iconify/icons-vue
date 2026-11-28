<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e53y4lb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e53y4lb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cube-x" /></template>
