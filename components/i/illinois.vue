<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_tx2tb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g_tx2tb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:illinois" /></template>
