<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lryz7mrcd.css';
import '../../css/r/rcmt1r3hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lryz7mrcd"/><path class="rcmt1r3hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:healthchecks" /></template>
