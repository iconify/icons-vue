<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvp-v1b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvp-v1b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-left-sharp-fill" /></template>
