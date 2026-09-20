<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1-_00qzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1-_00qzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:icinga-light" /></template>
