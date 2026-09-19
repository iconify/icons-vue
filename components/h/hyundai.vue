<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7z4jubhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7z4jubhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hyundai" /></template>
