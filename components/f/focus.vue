<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlubeppvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="vlubeppvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:focus" /></template>
