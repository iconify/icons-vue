<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wowm9d2iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wowm9d2iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:biohazard" /></template>
