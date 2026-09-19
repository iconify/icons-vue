<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynnrn-bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynnrn-bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:de-compress" /></template>
