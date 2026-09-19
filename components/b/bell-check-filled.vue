<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mccq_k88p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mccq_k88p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-check-filled" /></template>
