<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe81t3jjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe81t3jjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dropbox" /></template>
