<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsl7u1bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zsl7u1bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:handshake-angle" /></template>
