<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bocd00ptt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bocd00ptt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:coffee" /></template>
