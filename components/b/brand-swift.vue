<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb4--78so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb4--78so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-swift" /></template>
