<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhai0s2xq.css';
import '../../css/a/agy98qb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lhai0s2xq"/><path class="agy98qb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:alien" /></template>
