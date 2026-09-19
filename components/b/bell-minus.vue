<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1e2nrbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1e2nrbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bell-minus" /></template>
