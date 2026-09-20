<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp9l5nb1u.css';
import '../../css/v/v-lew9-av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jp9l5nb1u"/><path class="v-lew9-av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jotty" /></template>
