<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayhy9ccsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhy9ccsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cockpit" /></template>
