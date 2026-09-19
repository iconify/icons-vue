<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5w600x0k.css';
import '../../css/w/wz8ezaczc.css';
import '../../css/k/kvpzeiuru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a5w600x0k"/><circle class="wz8ezaczc"/><circle class="kvpzeiuru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ellipsis-horizontal-outline" /></template>
