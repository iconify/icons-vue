<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsg2jbb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fsg2jbb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:beer-solid" /></template>
