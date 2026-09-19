<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yke3jhb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yke3jhb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:dots-vertical" /></template>
