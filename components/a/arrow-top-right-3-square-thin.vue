<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak46xro0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak46xro0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-3-square-thin" /></template>
