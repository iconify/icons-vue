<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3dfkrlyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3dfkrlyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:app-window-check" /></template>
