<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymk_ijrgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ymk_ijrgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:hierarchy" /></template>
