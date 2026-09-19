<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs9vlybkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs9vlybkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bmw" /></template>
