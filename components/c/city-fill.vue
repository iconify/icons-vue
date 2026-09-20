<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlx-g_bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlx-g_bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:city-fill" /></template>
