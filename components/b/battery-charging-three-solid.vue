<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ea00rjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ea00rjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-charging-three-solid" /></template>
