<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz71u99bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oz71u99bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:filters" /></template>
