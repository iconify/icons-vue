<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfim0fz_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":830};
const content = `<path class="rfim0fz_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:cog" /></template>
