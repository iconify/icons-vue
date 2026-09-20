<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_coddk7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_coddk7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-alert" /></template>
