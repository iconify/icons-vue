<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1qz71bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1qz71bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arcane-light" /></template>
