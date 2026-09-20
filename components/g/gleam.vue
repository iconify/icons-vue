<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk3i2mpof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3i2mpof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gleam" /></template>
