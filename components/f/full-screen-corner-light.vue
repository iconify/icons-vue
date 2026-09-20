<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6hchz_se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6hchz_se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:full-screen-corner-light" /></template>
