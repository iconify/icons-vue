<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drgj1zbmh.css';
import '../../css/u/u4xg-pbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="drgj1zbmh"/><path class="u4xg-pbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bulb3" /></template>
