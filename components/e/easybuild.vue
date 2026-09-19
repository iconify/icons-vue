<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxmf65bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":355,"height":512};
const content = `<path class="xxmf65bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:easybuild" /></template>
