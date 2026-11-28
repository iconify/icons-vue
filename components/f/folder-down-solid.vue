<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u07v3c-nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u07v3c-nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-down-solid" /></template>
