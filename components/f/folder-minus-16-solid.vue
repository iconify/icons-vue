<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elgdx1llj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="elgdx1llj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-minus-16-solid" /></template>
