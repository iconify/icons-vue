<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbmop0bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":496};
const content = `<path class="wbmop0bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-4" /></template>
