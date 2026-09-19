<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jocuf1b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jocuf1b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:like" /></template>
