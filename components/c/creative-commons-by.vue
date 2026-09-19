<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mteqv3o6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mteqv3o6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:creative-commons-by" /></template>
