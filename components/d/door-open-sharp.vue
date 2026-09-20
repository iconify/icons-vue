<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i026q6bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i026q6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:door-open-sharp" /></template>
