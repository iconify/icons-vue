<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt1f1hbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt1f1hbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-c-filled" /></template>
