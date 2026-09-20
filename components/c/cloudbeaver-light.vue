<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiwyfacnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qiwyfacnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudbeaver-light" /></template>
