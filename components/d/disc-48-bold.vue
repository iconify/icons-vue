<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moyoz5fkv.css';
import '../../css/h/hlnkiidlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="hlnkiidlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:disc-48-bold" /></template>
