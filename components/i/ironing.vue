<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm_49ij3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_49ij3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ginetex:ironing" /></template>
