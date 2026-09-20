<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zviangknb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zviangknb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:four-box" /></template>
