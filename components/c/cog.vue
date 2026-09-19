<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wex2-nbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wex2-nbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cog" /></template>
