<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo3yfnbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qo3yfnbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:baby-in-swaddle" /></template>
