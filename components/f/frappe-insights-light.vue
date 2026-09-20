<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw0g3psjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bw0g3psjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-insights-light" /></template>
