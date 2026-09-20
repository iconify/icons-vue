<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvs0bnbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvs0bnbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jfrog" /></template>
