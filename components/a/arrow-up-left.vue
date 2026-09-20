<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd7j5cbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd7j5cbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:arrow-up-left" /></template>
