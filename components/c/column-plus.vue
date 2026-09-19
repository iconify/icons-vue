<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwxy09i0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwxy09i0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:column-plus" /></template>
