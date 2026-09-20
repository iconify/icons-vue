<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-0oyrb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-0oyrb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firebase-light" /></template>
