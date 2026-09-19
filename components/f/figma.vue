<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bja12wbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bja12wbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:figma" /></template>
