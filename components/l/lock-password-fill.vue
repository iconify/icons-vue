<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyaqjjqzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyaqjjqzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lock-password-fill" /></template>
