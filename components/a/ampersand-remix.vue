<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w16p4jb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w16p4jb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ampersand-remix" /></template>
