<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo0r8nblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo0r8nblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:graduation-cap" /></template>
