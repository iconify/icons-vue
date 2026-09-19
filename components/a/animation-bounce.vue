<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnccf7btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnccf7btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:animation-bounce" /></template>
