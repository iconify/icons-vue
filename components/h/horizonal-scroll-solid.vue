<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbd61esfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bbd61esfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:horizonal-scroll-solid" /></template>
