<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c55g4gb7e.css';
import '../../css/j/jkx5qo6th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c55g4gb7e"/><path class="jkx5qo6th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-double-left" /></template>
