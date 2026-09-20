<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svfxnlb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="svfxnlb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logtide" /></template>
