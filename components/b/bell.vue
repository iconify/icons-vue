<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh__jg8hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bh__jg8hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bell" /></template>
