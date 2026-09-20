<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnv1z5w0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnv1z5w0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heater" /></template>
