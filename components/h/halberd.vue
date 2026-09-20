<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-97j2bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="k-97j2bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:halberd" /></template>
