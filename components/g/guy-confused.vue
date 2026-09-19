<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa_oabncp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa_oabncp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-confused" /></template>
