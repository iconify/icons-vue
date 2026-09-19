<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgj0q-b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgj0q-b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:folder-conversion-one" /></template>
