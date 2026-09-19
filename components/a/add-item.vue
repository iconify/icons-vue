<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzve_6a2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzve_6a2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:add-item" /></template>
