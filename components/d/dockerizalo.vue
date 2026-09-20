<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgkqhtgri.css';
import '../../css/b/b7__w3xsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgkqhtgri"/><path class="b7__w3xsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockerizalo" /></template>
