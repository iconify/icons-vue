<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0y3xy14v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0y3xy14v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-down" /></template>
