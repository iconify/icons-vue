<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5s5n5bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5s5n5bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-airbnb" /></template>
