<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd-6131oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qd-6131oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:four-arrows" /></template>
