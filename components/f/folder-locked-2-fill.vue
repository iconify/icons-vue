<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re3r4xblg.css';
import '../../css/n/nq37i1bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re3r4xblg"/><path clip-rule="evenodd" class="nq37i1bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-locked-2-fill" /></template>
