<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goi3j1wdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goi3j1wdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-filled" /></template>
