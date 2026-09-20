<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivg15v0kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivg15v0kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lungs-off" /></template>
