<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn6ymjb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6ymjb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:htop" /></template>
