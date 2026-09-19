<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u32249byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u32249byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:display-pulse" /></template>
