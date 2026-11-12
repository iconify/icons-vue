<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfwme05gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfwme05gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:irs-dark" /></template>
