<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r84hslb4j.css';
import '../../css/w/wjj22sddn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r84hslb4j"/><path class="wjj22sddn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-reset" /></template>
