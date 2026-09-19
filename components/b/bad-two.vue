<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p26865b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p26865b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bad-two" /></template>
