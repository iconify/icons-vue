<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf0cojxsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf0cojxsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ambulance-solid" /></template>
