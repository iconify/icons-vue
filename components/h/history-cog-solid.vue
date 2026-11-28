<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2p4mcgud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2p4mcgud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:history-cog-solid" /></template>
