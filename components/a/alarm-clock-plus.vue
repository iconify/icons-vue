<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg7lrzbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg7lrzbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock-plus" /></template>
