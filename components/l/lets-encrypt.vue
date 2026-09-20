<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjtd44buw.css';
import '../../css/t/tkkp7gb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjtd44buw"/><path class="tkkp7gb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lets-encrypt" /></template>
