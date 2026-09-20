<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6ct7ybet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y6ct7ybet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:id-filled" /></template>
