<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v79h7tbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v79h7tbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeshard-dark" /></template>
