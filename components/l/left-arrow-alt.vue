<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt2b1obqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt2b1obqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:left-arrow-alt" /></template>
