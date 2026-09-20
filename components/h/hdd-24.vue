<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-sr4acye.css';
import '../../css/s/slj16rbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-sr4acye"/><path clip-rule="evenodd" class="slj16rbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hdd-24" /></template>
