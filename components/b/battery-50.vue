<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyqf5bucv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyqf5bucv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-50" /></template>
