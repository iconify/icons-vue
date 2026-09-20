<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw23jeecu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw23jeecu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:briefcase-conveyor-belt-solid" /></template>
