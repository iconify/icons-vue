<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kok4w2blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kok4w2blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dfir-iris" /></template>
