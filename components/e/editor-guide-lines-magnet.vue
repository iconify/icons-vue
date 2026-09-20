<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pat_cd9rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pat_cd9rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:editor-guide-lines-magnet" /></template>
