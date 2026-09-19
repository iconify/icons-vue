<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsfcpabqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsfcpabqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-telephone" /></template>
