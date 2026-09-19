<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ucx0b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l6ucx0b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ellipsis" /></template>
