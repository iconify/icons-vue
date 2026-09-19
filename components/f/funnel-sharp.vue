<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls78t9bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ls78t9bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:funnel-sharp" /></template>
