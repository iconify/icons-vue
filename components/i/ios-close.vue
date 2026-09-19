<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4igrcb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4igrcb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-close" /></template>
