<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtqlo9dtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtqlo9dtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-trace" /></template>
