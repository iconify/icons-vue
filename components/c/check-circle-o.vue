<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zviov1bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zviov1bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:check-circle-o" /></template>
