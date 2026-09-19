<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1vmbtb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":384};
const content = `<path class="l1vmbtb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:check-all" /></template>
