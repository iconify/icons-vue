<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mls71jonh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="mls71jonh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:deaf" /></template>
