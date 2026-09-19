<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjn_mkbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wjn_mkbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:close-circled" /></template>
