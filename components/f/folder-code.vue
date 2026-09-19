<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meqk0cb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="meqk0cb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-code" /></template>
