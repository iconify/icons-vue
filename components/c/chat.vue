<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypnl_3blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ypnl_3blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:chat" /></template>
