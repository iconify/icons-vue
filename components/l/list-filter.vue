<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poaev4p8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="poaev4p8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:list-filter" /></template>
