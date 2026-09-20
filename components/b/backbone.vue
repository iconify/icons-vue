<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph7pkv8aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph7pkv8aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:backbone" /></template>
