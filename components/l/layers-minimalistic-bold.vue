<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsikgs9ig.css';
import '../../css/s/s12m7vb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsikgs9ig"/><path clip-rule="evenodd" class="s12m7vb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layers-minimalistic-bold" /></template>
