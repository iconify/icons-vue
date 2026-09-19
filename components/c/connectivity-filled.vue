<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug4ifvviu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug4ifvviu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:connectivity-filled" /></template>
