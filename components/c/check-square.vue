<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd5hjkb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rd5hjkb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:check-square" /></template>
