<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq-zovx8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq-zovx8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user-pin" /></template>
