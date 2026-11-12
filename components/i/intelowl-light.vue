<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eomj11bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eomj11bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intelowl-light" /></template>
