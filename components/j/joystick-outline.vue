<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9773-b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e9773-b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:joystick-outline" /></template>
