<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihk4kgyae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihk4kgyae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:lightbulb-solid" /></template>
