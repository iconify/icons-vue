<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqtod85xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqtod85xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:irs-dark" /></template>
