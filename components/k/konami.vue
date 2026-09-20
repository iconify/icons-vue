<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr7aie1zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr7aie1zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:konami" /></template>
