<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5umz_b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5umz_b-r wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bold-gloss" /></template>
