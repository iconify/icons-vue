<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xogm_7b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xogm_7b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-dashboard" /></template>
