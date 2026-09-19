<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq0w_mbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="kq0w_mbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:calculator" /></template>
