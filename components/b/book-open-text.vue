<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meiu-pbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meiu-pbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-open-text" /></template>
