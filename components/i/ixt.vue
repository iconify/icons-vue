<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy29vdbwc.css';
import '../../css/p/p8jj4km5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy29vdbwc"/><path class="p8jj4km5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ixt" /></template>
