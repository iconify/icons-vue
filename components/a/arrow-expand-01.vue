<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzihj1__f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzihj1__f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-expand-01" /></template>
