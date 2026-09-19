<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgcnw6b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgcnw6b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ease-out" /></template>
