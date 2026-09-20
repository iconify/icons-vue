<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gndrgobtu.css';
import '../../css/v/vagvi2bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gndrgobtu"/><path class="vagvi2bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bookmarks-document-alternate-bold" /></template>
