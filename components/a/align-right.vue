<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsefpcb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsefpcb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:align-right" /></template>
