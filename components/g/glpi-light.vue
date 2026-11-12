<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftf97obuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftf97obuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glpi-light" /></template>
