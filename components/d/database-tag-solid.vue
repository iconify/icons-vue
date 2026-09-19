<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpng5jbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpng5jbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:database-tag-solid" /></template>
