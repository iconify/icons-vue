<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5biwmbup.css';
import '../../css/k/k8g6v0u2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5biwmbup"/><path class="k8g6v0u2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etherpad-light" /></template>
