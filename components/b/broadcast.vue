<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-zkvf-3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y-zkvf-3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:broadcast" /></template>
