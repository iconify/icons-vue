<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdaxkdb1q.css';
import '../../css/l/l-nhlab9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rdaxkdb1q"/><path class="l-nhlab9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dispatcharr" /></template>
