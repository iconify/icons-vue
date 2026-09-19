<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs6905b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fs6905b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:kx" /></template>
