<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-03f5vrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-03f5vrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clock-check-gloss" /></template>
