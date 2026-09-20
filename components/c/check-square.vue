<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq27eob6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iq27eob6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:check-square" /></template>
