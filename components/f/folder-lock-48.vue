<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h68nt64um.css';
import '../../css/h/h2gpnpb6w.css';
import '../../css/w/wweom8b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h68nt64um"/><path class="h2gpnpb6w"/><path class="wweom8b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-lock-48" /></template>
