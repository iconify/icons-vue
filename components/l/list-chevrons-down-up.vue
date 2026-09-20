<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pndt1acbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pndt1acbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-chevrons-down-up" /></template>
