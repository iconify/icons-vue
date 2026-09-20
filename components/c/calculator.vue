<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr79r7bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gr79r7bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:calculator" /></template>
