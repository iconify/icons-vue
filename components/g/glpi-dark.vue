<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi-oj1bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hi-oj1bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glpi-dark" /></template>
