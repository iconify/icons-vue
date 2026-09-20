<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug1c8l74s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug1c8l74s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-z-hexagon-solid" /></template>
