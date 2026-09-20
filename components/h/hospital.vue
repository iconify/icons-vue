<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tss4qzbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tss4qzbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:hospital" /></template>
