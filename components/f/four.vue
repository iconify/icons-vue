<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np-sermtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="np-sermtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:four" /></template>
