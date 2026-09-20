<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evsio0edl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evsio0edl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:link" /></template>
