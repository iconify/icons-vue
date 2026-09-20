<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjy91kbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjy91kbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:macro-filled" /></template>
