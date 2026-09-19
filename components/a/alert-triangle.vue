<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfqbxj_2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":408};
const content = `<path class="mfqbxj_2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alert-triangle" /></template>
