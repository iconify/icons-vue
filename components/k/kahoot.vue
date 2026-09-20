<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onn7hn6ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onn7hn6ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kahoot" /></template>
