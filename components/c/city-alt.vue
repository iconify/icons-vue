<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq-54j8na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="xq-54j8na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:city-alt" /></template>
