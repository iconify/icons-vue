<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wism3vaym.css';
import '../../css/n/nv5eburum.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><circle class="nv5eburum"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-bangladesh" /></template>
