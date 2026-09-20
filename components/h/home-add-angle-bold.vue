<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbca2owon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbca2owon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-add-angle-bold" /></template>
