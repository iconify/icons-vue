<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz3g_ob0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xz3g_ob0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jp-castle" /></template>
