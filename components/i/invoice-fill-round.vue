<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui_kllv4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui_kllv4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:invoice-fill-round" /></template>
