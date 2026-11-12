<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loycbjbia.css';
import '../../css/w/w3qyplb8m.css';
import '../../css/i/ihoo6dbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="loycbjbia"/><path class="w3qyplb8m"/><path class="ihoo6dbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domainmod-light" /></template>
