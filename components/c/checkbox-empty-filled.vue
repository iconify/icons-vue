<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voasgl06y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="voasgl06y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkbox-empty-filled" /></template>
