<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8dfn-r_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8dfn-r_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-short-sharp-fill" /></template>
