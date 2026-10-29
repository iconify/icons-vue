<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8muh1b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8muh1b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-info-solid" /></template>
