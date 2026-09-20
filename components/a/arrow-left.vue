<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1v0vkkgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="v1v0vkkgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-left" /></template>
