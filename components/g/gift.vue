<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk5yjk1vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zk5yjk1vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gift" /></template>
