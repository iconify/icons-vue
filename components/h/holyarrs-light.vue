<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0_3hsgpg.css';
import '../../css/h/hw9pzduln.css';
import '../../css/x/x8hovebwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s0_3hsgpg"/><path class="hw9pzduln"/><path class="x8hovebwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:holyarrs-light" /></template>
