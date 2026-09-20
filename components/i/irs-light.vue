<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boi9rwbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="boi9rwbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:irs-light" /></template>
