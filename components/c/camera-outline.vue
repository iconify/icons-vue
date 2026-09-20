<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abc-f6w-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="abc-f6w-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:camera-outline" /></template>
