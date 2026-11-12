<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaa_36bkr.css';
import '../../css/a/azcm8kehl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zaa_36bkr"/><path class="azcm8kehl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duckduckgo-dark" /></template>
