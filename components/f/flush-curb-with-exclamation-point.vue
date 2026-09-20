<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu2ujfbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xu2ujfbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flush-curb-with-exclamation-point" /></template>
