<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc26d0b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc26d0b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:daze-square-solid" /></template>
