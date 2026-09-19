<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8oh7p4lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x8oh7p4lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:add-subset" /></template>
