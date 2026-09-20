<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e86ldwm9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e86ldwm9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graylog-dark" /></template>
