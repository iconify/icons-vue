<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6a5nq_5m.css';
import '../../css/l/lw80oobkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6a5nq_5m"/><path class="lw80oobkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-power" /></template>
