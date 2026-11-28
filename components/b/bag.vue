<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c41vt3bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c41vt3bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bag" /></template>
