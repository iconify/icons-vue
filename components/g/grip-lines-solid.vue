<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y21owvl3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y21owvl3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grip-lines-solid" /></template>
