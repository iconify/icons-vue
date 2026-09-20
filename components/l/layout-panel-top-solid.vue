<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymr08vb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymr08vb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-panel-top-solid" /></template>
