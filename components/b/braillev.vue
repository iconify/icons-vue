<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7ycth5rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="r7ycth5rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillev" /></template>
