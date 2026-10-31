<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/d7_8r7b7c.css';
import '../../css/m/mcd_p02bq.css';
import '../../css/k/k41b5wbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="d7_8r7b7c wm-shadow"/><path class="mcd_p02bq wm-shadow"/><path class="k41b5wbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:atom" /></template>
