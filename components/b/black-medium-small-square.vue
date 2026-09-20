<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh6n15bwy.css';
import '../../css/u/umdrjybhb.css';
import '../../css/b/bw_zhbbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bh6n15bwy"/><path class="umdrjybhb"/><path class="bw_zhbbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-medium-small-square" /></template>
