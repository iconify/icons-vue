<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmm6kfbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmm6kfbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-fill" /></template>
