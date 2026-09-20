<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9hwx3hly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="x9hwx3hly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bookmark" /></template>
