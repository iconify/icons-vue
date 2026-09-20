<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv0bzkbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dv0bzkbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bench-with-backrest" /></template>
