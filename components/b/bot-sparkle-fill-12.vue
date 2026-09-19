<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2fs_cbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l2fs_cbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bot-sparkle-fill-12" /></template>
