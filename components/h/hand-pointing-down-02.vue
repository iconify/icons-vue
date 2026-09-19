<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxf4d6pbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxf4d6pbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-down-02" /></template>
