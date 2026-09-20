<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teunmzp6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="teunmzp6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lab-dash-light" /></template>
