<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfolds2ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xfolds2ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:happy-face-with-face-mask-in-circle-outline" /></template>
