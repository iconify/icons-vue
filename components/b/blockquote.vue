<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he1rpcc4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he1rpcc4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:blockquote" /></template>
