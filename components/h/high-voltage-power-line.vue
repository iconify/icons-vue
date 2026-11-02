<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3qt8gsqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3qt8gsqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-voltage-power-line" /></template>
