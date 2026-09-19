<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9je29i3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p9je29i3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:code-one" /></template>
