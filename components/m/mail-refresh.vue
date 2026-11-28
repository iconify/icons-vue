<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbxl8bcqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbxl8bcqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-refresh" /></template>
