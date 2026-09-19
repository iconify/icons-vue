<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv9yunb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yv9yunb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-badge-stroke-12" /></template>
