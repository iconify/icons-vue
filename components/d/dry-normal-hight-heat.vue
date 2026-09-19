<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-3hdh2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb-3hdh2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:dry-normal-hight-heat" /></template>
