<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgk9v4g2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dgk9v4g2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:buy-me-a-coffee" /></template>
