<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gizbtibcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gizbtibcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:adjust" /></template>
