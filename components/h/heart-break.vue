<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4yq3meke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4yq3meke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:heart-break" /></template>
