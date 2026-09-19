<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5-lgcc0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u5-lgcc0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:identification" /></template>
