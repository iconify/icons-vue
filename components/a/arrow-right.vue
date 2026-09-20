<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp_xqfbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp_xqfbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-right" /></template>
