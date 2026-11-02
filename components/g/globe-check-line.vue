<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruyg2bc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruyg2bc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-check-line" /></template>
