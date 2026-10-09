<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psemm7bpq.css';
import '../../css/y/yeivt_bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="psemm7bpq"/><path class="yeivt_bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hash-48" /></template>
