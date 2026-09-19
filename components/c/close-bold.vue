<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxqxg_35p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxqxg_35p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-bold" /></template>
