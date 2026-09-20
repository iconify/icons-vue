<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz41yccml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz41yccml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:desk-lamp" /></template>
