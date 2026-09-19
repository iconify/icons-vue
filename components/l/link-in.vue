<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-io5hbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x-io5hbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:link-in" /></template>
