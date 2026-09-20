<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxfn37b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxfn37b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:layouts-top-three-columns" /></template>
