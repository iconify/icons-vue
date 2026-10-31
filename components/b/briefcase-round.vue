<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwtte82_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwtte82_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:briefcase-round" /></template>
