<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsxry348y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsxry348y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:eufy-doorbell" /></template>
