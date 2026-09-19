<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9mcn14ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s9mcn14ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heading-fill-12" /></template>
