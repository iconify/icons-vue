<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia86285af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia86285af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:backward-step-outline" /></template>
