<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmmy86dde.css';
import '../../css/s/sva9mubnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmmy86dde"/><path class="sva9mubnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feeds-fun" /></template>
