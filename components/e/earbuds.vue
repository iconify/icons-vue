<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm0rkj2aq.css';
import '../../css/s/sjyb2qfru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm0rkj2aq"/><path class="sjyb2qfru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:earbuds" /></template>
