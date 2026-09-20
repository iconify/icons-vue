<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vism6qblg.css';
import '../../css/n/nnx_4qb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vism6qblg"/><path class="nnx_4qb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-refresh-light" /></template>
