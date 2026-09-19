<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln2xiy3fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln2xiy3fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-anchor" /></template>
