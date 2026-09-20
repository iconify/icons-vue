<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd1d7sb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qd1d7sb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ampersand" /></template>
