<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc291pbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gc291pbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:device-driver" /></template>
