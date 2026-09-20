<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0557kbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0557kbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-beam-solid" /></template>
