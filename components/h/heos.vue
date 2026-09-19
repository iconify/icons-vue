<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eabh0cstn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eabh0cstn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:heos" /></template>
