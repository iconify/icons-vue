<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9x9-c_l.css';
import '../../css/m/mn1zs2tiq.css';
import '../../css/x/xdak-07ba.css';
import '../../css/g/gpf3pvb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/><path class="mn1zs2tiq"/><path class="xdak-07ba"/><path class="gpf3pvb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-sync-48" /></template>
