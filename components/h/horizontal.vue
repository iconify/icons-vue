<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iff0e9biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":687,"height":717};
const content = `<path class="iff0e9biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:horizontal" /></template>
