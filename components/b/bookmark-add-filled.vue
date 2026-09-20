<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj95tcc7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj95tcc7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-add-filled" /></template>
