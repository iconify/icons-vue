<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw672wuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xrw672wuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:disable-heart-solid" /></template>
