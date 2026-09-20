<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laf7_tbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laf7_tbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-signal-filled" /></template>
