<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slz8b_t7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="slz8b_t7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-sun-outline" /></template>
