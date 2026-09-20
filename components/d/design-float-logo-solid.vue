<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4cnuojok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g4cnuojok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:design-float-logo-solid" /></template>
