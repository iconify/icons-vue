<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yftn1vhpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yftn1vhpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bookmark-alt" /></template>
