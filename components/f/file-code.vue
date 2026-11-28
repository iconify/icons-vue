<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf0wxgfup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf0wxgfup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-code" /></template>
