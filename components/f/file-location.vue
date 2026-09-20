<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stgard2ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stgard2ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-location" /></template>
