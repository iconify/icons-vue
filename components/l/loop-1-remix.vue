<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b83i4cbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b83i4cbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:loop-1-remix" /></template>
