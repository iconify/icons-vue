<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3l9e9m6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3l9e9m6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-add" /></template>
