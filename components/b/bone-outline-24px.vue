<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk2qihvhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk2qihvhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-outline-24px" /></template>
