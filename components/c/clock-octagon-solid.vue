<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl99x3mqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl99x3mqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-octagon-solid" /></template>
