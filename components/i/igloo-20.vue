<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a27-2bahm.css';
import '../../css/i/i1hgre67m.css';
import '../../css/k/kac4dlpam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a27-2bahm"/><path class="i1hgre67m"/><path class="kac4dlpam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:igloo-20" /></template>
