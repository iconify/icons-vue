<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3wpccc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b3wpccc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-spotify" /></template>
