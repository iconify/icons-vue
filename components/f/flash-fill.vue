<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlb_45vzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlb_45vzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:flash-fill" /></template>
