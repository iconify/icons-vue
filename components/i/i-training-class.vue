<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii5gop2lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ii5gop2lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:i-training-class" /></template>
