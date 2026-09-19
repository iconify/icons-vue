<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsawk4bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsawk4bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:block-six" /></template>
