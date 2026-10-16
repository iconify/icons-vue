<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cws-8tb1t.css';
import '../../css/a/aktl5czru.css';
import '../../css/m/m86vp2brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cws-8tb1t"/><path class="aktl5czru"/><path class="m86vp2brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-tree-48-bold" /></template>
