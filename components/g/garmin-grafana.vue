<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqiziocuh.css';
import '../../css/e/e9p8wp9jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqiziocuh"/><path class="e9p8wp9jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garmin-grafana" /></template>
