<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv3ahtb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fv3ahtb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-dna" /></template>
