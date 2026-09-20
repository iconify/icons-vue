<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czowfub8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czowfub8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:five-solid" /></template>
