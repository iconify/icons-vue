<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4jzllbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z4jzllbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:happy-face-with-face-mask-in-circle" /></template>
