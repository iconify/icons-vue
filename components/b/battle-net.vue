<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skqg7ttpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="skqg7ttpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:battle-net" /></template>
