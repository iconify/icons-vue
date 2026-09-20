<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhyhz9zwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhyhz9zwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bed-outline" /></template>
