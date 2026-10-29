<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzci_0zyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzci_0zyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cake-slice" /></template>
