<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/s-47tuq-b.css';
import '../../css/p/pc0h08v4d.css';
import '../../css/x/x3c8exbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="s-47tuq-b wm-shadow"/><path class="pc0h08v4d wm-shadow"/><path class="x3c8exbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:a-large-small" /></template>
