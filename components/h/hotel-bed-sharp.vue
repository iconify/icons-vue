<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de472wbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de472wbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:hotel-bed-sharp" /></template>
