<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juewm1baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="juewm1baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:magnifier" /></template>
