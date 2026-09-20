<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llnxsn2pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llnxsn2pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:hackernoon" /></template>
