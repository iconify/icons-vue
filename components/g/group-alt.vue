<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz-p99uxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz-p99uxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:group-alt" /></template>
