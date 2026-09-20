<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha3hny2-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha3hny2-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-hexagon" /></template>
