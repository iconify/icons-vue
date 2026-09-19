<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5hs643eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5hs643eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:leaf" /></template>
