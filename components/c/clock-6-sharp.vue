<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muui0pbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muui0pbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-6-sharp" /></template>
