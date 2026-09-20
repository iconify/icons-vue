<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt9z3uuyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt9z3uuyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-chrome-light" /></template>
