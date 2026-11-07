<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqtyd2syu.css';
import '../../css/t/tzom42bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqtyd2syu"/><path class="tzom42bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-heart-minimalistic-bold" /></template>
