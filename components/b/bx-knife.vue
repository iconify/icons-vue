<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn84b3bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn84b3bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-knife" /></template>
