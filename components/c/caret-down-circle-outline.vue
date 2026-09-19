<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crkvjda8n.css';
import '../../css/l/lsg5j7ibl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="crkvjda8n"/><path class="lsg5j7ibl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:caret-down-circle-outline" /></template>
