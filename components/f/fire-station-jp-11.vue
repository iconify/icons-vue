<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgk16pb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="mgk16pb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fire-station-jp-11" /></template>
