<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hey_i9tsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hey_i9tsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-refresh" /></template>
