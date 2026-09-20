<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwglqvu_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwglqvu_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:border-alt" /></template>
