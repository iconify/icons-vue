<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlr7esbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlr7esbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrows-right-filled" /></template>
