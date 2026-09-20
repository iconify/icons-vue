<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt-78blmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt-78blmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kettle-empty" /></template>
