<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g03q9xe2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g03q9xe2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ambulance" /></template>
