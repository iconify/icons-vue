<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt75vhbsg.css';
import '../../css/y/y4cd3rkme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kt75vhbsg"/><path class="y4cd3rkme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:backuppc-dark" /></template>
