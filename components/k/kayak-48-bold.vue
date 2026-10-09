<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9903qb7k.css';
import '../../css/u/uwd9spbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b9903qb7k"/><path class="uwd9spbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kayak-48-bold" /></template>
