<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7d_9oypd.css';
import '../../css/l/luvx9bb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7d_9oypd"/><path class="luvx9bb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-watchdog-dark" /></template>
