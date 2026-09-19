<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1do2fb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x1do2fb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:apple-small-filled" /></template>
