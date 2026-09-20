<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxbt_k8yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxbt_k8yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-arrow-left" /></template>
