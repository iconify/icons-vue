<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pot4xccpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pot4xccpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-rain-wind" /></template>
