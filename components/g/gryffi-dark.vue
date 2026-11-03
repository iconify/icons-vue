<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2gqtqqut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2gqtqqut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gryffi-dark" /></template>
