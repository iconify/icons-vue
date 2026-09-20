<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p03g2jbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p03g2jbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grass-fill" /></template>
