<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7a5cccqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7a5cccqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-medium" /></template>
