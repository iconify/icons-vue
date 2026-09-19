<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k179mzbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k179mzbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:loading-two" /></template>
