<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppoewyanq.css';
import '../../css/m/mq10tpb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ppoewyanq"/><path class="mq10tpb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-supabase" /></template>
