<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2gcvubkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2gcvubkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:library-big-filled" /></template>
