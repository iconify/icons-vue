<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo9-u_9hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mo9-u_9hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:broom-solid" /></template>
