<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9uczfoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9uczfoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:enterprise-filled" /></template>
