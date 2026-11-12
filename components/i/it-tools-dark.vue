<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i104_jbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i104_jbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:it-tools-dark" /></template>
