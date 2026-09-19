<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff7b9fi-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="ff7b9fi-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card" /></template>
