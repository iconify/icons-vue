<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w14ec4bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w14ec4bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-dot" /></template>
