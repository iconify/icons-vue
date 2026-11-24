<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-9vpvbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-9vpvbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bacon-filled" /></template>
