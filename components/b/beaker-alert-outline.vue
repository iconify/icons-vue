<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbg4zxbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbg4zxbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-alert-outline" /></template>
