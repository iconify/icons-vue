<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plq1snb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plq1snb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:internet-archive" /></template>
