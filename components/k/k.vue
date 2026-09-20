<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw7hgimri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iw7hgimri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:k" /></template>
