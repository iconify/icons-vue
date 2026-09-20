<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mge4dfs-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mge4dfs-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dadabik-light" /></template>
