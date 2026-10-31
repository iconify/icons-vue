<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/o/owdh5nbuy.css';
import '../../css/r/r-m662bys.css';
import '../../css/n/nktcn_w5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="owdh5nbuy wm-shadow"/><path class="r-m662bys wm-shadow"/><path class="nktcn_w5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chart-bar-decreasing" /></template>
