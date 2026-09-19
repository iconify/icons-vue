<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avkbrq_dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avkbrq_dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-sparkles-filled" /></template>
