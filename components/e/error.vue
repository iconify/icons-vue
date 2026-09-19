<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7368p70m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7368p70m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:error" /></template>
