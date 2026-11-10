<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkps23bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkps23bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-key" /></template>
