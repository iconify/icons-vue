<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j50tsqbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j50tsqbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-top-outline" /></template>
