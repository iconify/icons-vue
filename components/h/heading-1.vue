<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/medowg-8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="medowg-8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:heading-1" /></template>
