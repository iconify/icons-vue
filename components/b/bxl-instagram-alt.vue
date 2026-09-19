<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9tqfebse.css';
import '../../css/m/m7aw91b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9tqfebse"/><circle class="m7aw91b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-instagram-alt" /></template>
