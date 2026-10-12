<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdekmlb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sdekmlb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-turkish-lira-filled" /></template>
