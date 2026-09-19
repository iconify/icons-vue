<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu5jp-b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qu5jp-b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:construction-cone-solid" /></template>
