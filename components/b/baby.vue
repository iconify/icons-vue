<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8g_54abo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="s8g_54abo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:baby" /></template>
