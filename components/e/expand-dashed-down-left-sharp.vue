<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlvzzwmpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlvzzwmpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-left-sharp" /></template>
