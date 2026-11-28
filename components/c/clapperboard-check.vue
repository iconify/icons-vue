<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb6cpgbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb6cpgbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clapperboard-check" /></template>
