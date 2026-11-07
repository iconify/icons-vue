<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyax-g3ph.css';
import '../../css/j/jik0uqbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zyax-g3ph"/><path class="jik0uqbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-download-bold" /></template>
