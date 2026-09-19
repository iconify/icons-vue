<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se4_yi4nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se4_yi4nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cherry-filled" /></template>
