<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz3cb7byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz3cb7byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:astroc" /></template>
