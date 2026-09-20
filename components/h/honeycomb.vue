<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9qu2hl1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50.6,"height":48};
const content = `<path class="w9qu2hl1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:honeycomb" /></template>
