<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3x8ayb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="p3x8ayb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:gps-receiving" /></template>
