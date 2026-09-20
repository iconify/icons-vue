<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn4z0js2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zn4z0js2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-map-pin-with-dot" /></template>
