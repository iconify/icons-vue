<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfg0gebtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vfg0gebtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:briefcase" /></template>
