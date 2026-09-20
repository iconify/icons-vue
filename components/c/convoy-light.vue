<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2agh85ja.css';
import '../../css/l/l0ifl0rlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2agh85ja"/><path class="l0ifl0rlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:convoy-light" /></template>
