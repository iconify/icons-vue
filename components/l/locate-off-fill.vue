<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfe747b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfe747b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:locate-off-fill" /></template>
