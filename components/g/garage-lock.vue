<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_p4fnuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la_p4fnuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:garage-lock" /></template>
