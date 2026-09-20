<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6n_f-bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6n_f-bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-alert-outline" /></template>
