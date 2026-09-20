<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p643z7b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p643z7b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:jackhammer" /></template>
