<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jli2whjga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jli2whjga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-alert-outline" /></template>
