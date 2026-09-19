<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfqbr2bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mfqbr2bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-dashed" /></template>
