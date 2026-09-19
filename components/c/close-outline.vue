<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5yn9ndtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5yn9ndtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:close-outline" /></template>
