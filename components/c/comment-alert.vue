<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7qvsivew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="q7qvsivew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-alert" /></template>
