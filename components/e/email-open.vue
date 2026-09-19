<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzi65lbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="lzi65lbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:email-open" /></template>
