<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg1t_dv8x.css';
import '../../css/c/cgf21cybt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg1t_dv8x"/><path clip-rule="evenodd" class="cgf21cybt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:file-download-outline" /></template>
