<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kred8wbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kred8wbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-edit" /></template>
