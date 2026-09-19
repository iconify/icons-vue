<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih0_ebcle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ih0_ebcle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:arm-circumference-outline" /></template>
