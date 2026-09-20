<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giv9vwr2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4.5};
const content = `<path class="giv9vwr2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:dashboard-f" /></template>
