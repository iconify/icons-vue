<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggyrz3unk.css';
import '../../css/c/ci8zk7bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ggyrz3unk"/><path class="ci8zk7bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fast-forward-20-bold" /></template>
