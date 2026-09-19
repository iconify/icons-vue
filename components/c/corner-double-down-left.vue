<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz14hze0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz14hze0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-double-down-left" /></template>
