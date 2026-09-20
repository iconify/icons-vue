<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2yj4pmym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t2yj4pmym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:inquiry-filled" /></template>
