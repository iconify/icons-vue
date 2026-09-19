<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hemi351pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hemi351pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:artificial-hive" /></template>
