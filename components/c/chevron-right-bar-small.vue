<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh57bvagt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qh57bvagt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-right-bar-small" /></template>
