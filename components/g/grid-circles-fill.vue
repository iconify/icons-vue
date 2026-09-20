<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzlfh-bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzlfh-bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-fill" /></template>
