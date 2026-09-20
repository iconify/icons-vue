<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2h4lew8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2h4lew8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-excel-outline" /></template>
