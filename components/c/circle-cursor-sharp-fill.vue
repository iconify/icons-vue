<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-pxawmvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-pxawmvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-cursor-sharp-fill" /></template>
