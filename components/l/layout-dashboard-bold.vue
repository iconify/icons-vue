<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vby78g3_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vby78g3_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:layout-dashboard-bold" /></template>
