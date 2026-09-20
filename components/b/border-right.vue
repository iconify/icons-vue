<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m58mo2jnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m58mo2jnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:border-right" /></template>
