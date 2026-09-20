<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o25rrxbqg.css';
import '../../css/k/ky67sqbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o25rrxbqg"/><path class="ky67sqbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adventurelog-dark" /></template>
