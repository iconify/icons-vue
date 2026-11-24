<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4d3_byfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n4d3_byfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bean-filled" /></template>
