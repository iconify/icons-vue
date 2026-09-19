<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpeq1mbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpeq1mbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-lightning-filled" /></template>
