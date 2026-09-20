<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om_becc8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="om_becc8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:landuse-11" /></template>
