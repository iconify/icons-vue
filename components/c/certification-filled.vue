<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx7lam2sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx7lam2sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:certification-filled" /></template>
