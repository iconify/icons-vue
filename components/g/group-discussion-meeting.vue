<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwhhydjyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwhhydjyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:group-discussion-meeting" /></template>
