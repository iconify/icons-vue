<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfc5bebsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfc5bebsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:magic-wand" /></template>
