<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuuepsb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuuepsb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fladder-light" /></template>
