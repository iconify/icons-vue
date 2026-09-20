<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ski76bcvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ski76bcvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:linkedin-alt" /></template>
