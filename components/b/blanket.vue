<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl1qd3ihr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1qd3ihr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:blanket" /></template>
