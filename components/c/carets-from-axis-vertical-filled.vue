<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtw_a9i1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtw_a9i1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carets-from-axis-vertical-filled" /></template>
