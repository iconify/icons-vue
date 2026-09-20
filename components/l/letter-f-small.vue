<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og5hd0y1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og5hd0y1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-f-small" /></template>
