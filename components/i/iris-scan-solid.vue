<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4frg809p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q4frg809p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:iris-scan-solid" /></template>
