<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inq4aqb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="inq4aqb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:drum-solid" /></template>
