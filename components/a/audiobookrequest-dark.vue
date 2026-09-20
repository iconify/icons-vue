<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw_389blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mw_389blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiobookrequest-dark" /></template>
