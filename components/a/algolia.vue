<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj80jg_eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj80jg_eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:algolia" /></template>
