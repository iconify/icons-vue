<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6sq5sb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6sq5sb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:building3-filled" /></template>
