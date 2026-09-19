<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6d97fbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6d97fbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-circle-plus-filled" /></template>
