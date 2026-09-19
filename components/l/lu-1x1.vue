<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6w7p4bnr.css';
import '../../css/a/aw9rmcz9o.css';
import '../../css/g/g8mz2db_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6w7p4bnr"/><path class="aw9rmcz9o"/><path class="g8mz2db_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:lu-1x1" /></template>
