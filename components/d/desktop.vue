<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsxs_ubkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsxs_ubkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:desktop" /></template>
