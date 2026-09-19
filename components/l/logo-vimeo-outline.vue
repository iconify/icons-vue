<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae8qgnbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae8qgnbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-vimeo-outline" /></template>
