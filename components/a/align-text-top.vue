<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq_hm8yes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wq_hm8yes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-text-top" /></template>
