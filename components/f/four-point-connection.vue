<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7a51mr5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7a51mr5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:four-point-connection" /></template>
