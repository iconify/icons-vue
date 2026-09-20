<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2voi_5he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="u2voi_5he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:brush-solid" /></template>
