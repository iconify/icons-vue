<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoz70-7uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoz70-7uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:list-ul" /></template>
