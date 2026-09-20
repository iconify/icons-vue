<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6lud-ixf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g6lud-ixf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dice-six-solid" /></template>
