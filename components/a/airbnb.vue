<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7i1ukt-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7i1ukt-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:airbnb" /></template>
