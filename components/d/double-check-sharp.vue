<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxl6s7b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxl6s7b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:double-check-sharp" /></template>
