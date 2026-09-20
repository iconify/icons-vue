<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la31dzc5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="la31dzc5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coughing-face-with-spittle-in-circle" /></template>
