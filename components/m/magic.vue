<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkwely5ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkwely5ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:magic" /></template>
