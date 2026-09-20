<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6ug91b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m6ug91b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-alt-circle-down" /></template>
