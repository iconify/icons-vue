<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt-mm9atl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bt-mm9atl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:five-ellipses" /></template>
