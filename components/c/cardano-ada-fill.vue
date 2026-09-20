<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6h_-78-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6h_-78-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cardano-ada-fill" /></template>
