<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7d6o3kik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7d6o3kik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:double-check-fill" /></template>
