<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiavo5szk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiavo5szk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2" /></template>
