<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg82h9bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg82h9bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:framer" /></template>
