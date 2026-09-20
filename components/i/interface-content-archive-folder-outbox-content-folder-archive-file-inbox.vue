<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqha5oyiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oqha5oyiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-content-archive-folder-outbox-content-folder-archive-file-inbox" /></template>
