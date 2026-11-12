<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si0pir4by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="si0pir4by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composerize-light" /></template>
