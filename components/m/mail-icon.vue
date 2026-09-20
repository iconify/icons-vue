<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdaxgpfdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vdaxgpfdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mail-icon" /></template>
