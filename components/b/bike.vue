<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pukg5ji7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pukg5ji7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:bike" /></template>
