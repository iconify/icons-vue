<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwow64hay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qwow64hay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bag-of-trash-with-stink" /></template>
