<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dba77acgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dba77acgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:dot-grid-fill" /></template>
