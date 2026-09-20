<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw91fybat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uw91fybat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fingerprint-1-remix" /></template>
