<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-iptellt.css';
import '../../css/o/owrwif8bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-iptellt"/><path class="owrwif8bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-carousel-filled" /></template>
