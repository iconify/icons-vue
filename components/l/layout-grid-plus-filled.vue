<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6jx3xtgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6jx3xtgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-grid-plus-filled" /></template>
