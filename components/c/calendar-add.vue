<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4tmepvdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4tmepvdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-add" /></template>
