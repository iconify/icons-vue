<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ff30bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9ff30bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:liwan" /></template>
