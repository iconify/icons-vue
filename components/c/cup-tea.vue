<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xop-2uvkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xop-2uvkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cup-tea" /></template>
