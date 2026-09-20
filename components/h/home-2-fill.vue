<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p53oejbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p53oejbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-2-fill" /></template>
