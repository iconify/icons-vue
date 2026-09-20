<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax92y6w3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax92y6w3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-broken" /></template>
