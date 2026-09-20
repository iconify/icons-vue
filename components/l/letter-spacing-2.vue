<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp0--ebus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp0--ebus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:letter-spacing-2" /></template>
