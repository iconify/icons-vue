<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4bg5ebsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4bg5ebsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-refresh" /></template>
