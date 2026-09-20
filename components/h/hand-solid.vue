<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geex6gb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geex6gb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hand-solid" /></template>
