<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbgak7bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgak7bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ko-fi" /></template>
