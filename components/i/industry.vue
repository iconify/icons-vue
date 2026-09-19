<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh5c8rm5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="jh5c8rm5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:industry" /></template>
