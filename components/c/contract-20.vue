<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-g74icta.css';
import '../../css/o/og5hr9b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="og5hr9b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contract-20" /></template>
