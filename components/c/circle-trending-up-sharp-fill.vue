<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_3l2v-ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_3l2v-ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-trending-up-sharp-fill" /></template>
