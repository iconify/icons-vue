<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tngkkybgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tngkkybgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-fill" /></template>
