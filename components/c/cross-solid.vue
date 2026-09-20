<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mly2-fb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mly2-fb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cross-solid" /></template>
