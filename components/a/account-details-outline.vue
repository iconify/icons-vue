<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofssroh6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofssroh6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-details-outline" /></template>
