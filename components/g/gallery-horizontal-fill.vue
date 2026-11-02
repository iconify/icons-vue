<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr29-dgdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr29-dgdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-horizontal-fill" /></template>
