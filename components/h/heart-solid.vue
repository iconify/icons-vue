<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usmgq6brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usmgq6brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:heart-solid" /></template>
