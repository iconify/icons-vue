<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfuomw56r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfuomw56r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:binoculars-solid" /></template>
