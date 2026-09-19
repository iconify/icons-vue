<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cco7ibccm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cco7ibccm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:down-long" /></template>
