<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpr_y2baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpr_y2baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-t" /></template>
