<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6j1x8b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k6j1x8b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:facebook" /></template>
