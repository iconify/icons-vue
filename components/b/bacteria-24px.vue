<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuf32_b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuf32_b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bacteria-24px" /></template>
