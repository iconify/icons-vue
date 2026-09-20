<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4-4i3wlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m4-4i3wlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clickhouse-light" /></template>
