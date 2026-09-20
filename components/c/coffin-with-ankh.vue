<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0x_n6utq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p0x_n6utq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-ankh" /></template>
