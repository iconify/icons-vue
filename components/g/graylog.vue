<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7dcb4o8w.css';
import '../../css/x/x6gvil5vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k7dcb4o8w"/><path class="x6gvil5vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graylog" /></template>
