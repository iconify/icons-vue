<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzk05gb5l.css';
import '../../css/d/d86a3vbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzk05gb5l"/><path class="d86a3vbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-screenconnect" /></template>
