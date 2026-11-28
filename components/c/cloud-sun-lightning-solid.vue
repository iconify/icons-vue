<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yis2penob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yis2penob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-sun-lightning-solid" /></template>
