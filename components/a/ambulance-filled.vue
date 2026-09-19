<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjcpyjl4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjcpyjl4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ambulance-filled" /></template>
