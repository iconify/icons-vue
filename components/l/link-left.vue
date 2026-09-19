<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeu03xbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aeu03xbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:link-left" /></template>
