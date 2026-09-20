<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgm1g8b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mgm1g8b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:export-progress" /></template>
