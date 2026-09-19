<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v198n4rdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v198n4rdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:confused-filled" /></template>
