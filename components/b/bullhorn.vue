<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf41albxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf41albxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bullhorn" /></template>
