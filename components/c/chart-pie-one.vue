<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwyah0bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwyah0bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-pie-one" /></template>
