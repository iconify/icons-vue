<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq0l3cvad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq0l3cvad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-edit-outline" /></template>
