<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcha-w7qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcha-w7qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-bold" /></template>
