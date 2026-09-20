<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwn9qcb9d.css';
import '../../css/l/lpk12-20r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwn9qcb9d"/><path class="lpk12-20r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lufin" /></template>
