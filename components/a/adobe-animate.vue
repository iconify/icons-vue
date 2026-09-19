<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h07slsb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h07slsb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adobe-animate" /></template>
