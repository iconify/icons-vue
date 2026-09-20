<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdkeg8bno.css';
import '../../css/r/ro17tb5-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bdkeg8bno"/><path class="ro17tb5-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anyappstart" /></template>
