<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf324w_xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gf324w_xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-merge-filled" /></template>
