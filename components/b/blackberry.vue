<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu4h1fb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu4h1fb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:blackberry" /></template>
