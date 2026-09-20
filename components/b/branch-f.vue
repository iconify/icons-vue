<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4mcjdb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="d4mcjdb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:branch-f" /></template>
