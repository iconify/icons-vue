<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubfefht9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubfefht9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:between-vertical-end-filled" /></template>
