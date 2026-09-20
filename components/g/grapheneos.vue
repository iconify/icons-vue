<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpt1axmyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dpt1axmyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grapheneos" /></template>
