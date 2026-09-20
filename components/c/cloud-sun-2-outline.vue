<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiqq3fbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fiqq3fbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-sun-2-outline" /></template>
