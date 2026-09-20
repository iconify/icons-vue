<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p94whofhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p94whofhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-none" /></template>
