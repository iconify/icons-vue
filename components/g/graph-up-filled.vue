<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0136rbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0136rbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:graph-up-filled" /></template>
