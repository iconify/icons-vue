<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb95u623t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb95u623t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arachnid-outline" /></template>
