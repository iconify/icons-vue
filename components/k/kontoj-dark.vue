<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlgf8l19l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlgf8l19l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kontoj-dark" /></template>
