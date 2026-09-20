<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh85zl5bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uh85zl5bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intelowl-light" /></template>
