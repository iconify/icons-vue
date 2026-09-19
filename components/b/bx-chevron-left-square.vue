<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdzi00bpt.css';
import '../../css/p/pcz3a9bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="pcz3a9bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-chevron-left-square" /></template>
