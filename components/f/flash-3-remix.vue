<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgnx0cq-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bgnx0cq-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-3-remix" /></template>
