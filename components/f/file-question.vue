<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu66rw_rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu66rw_rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-question" /></template>
