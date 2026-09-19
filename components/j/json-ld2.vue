<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mblqj2cwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mblqj2cwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:json-ld2" /></template>
