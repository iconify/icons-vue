<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd8kbrbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="nd8kbrbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cloud-upload-26" /></template>
