<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnjxs1h6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnjxs1h6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graylog-light" /></template>
