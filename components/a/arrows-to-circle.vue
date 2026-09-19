<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmto9yz5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qmto9yz5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-to-circle" /></template>
