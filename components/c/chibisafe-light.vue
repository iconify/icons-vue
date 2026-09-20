<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fagntxw4g.css';
import '../../css/t/tqmas5pkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fagntxw4g"/><path class="tqmas5pkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chibisafe-light" /></template>
