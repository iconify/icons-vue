<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3tx3lj_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3tx3lj_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:comb" /></template>
