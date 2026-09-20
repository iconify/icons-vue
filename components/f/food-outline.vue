<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ias0wlihu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ias0wlihu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-outline" /></template>
