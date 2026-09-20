<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4sv1zb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4sv1zb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bezier-curve-solid" /></template>
