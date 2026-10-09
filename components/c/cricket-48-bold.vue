<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_721kb1n.css';
import '../../css/k/k1mcwabef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_721kb1n"/><path class="k1mcwabef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cricket-48-bold" /></template>
