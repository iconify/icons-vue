<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2p9e0byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f2p9e0byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:camping-tent-solid" /></template>
