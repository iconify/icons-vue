<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdio18b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdio18b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-right-outline" /></template>
