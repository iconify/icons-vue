<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7f000we.css';
import '../../css/m/mz1_d65yo.css';
import '../../css/i/iq22m6bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym7f000we"/><path class="mz1_d65yo"/><path class="iq22m6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:documents-bold" /></template>
