<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em1uhysbp.css';
import '../../css/w/wp14jkbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="em1uhysbp"/><path class="wp14jkbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-watchdog-light" /></template>
