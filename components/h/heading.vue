<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbs0qqb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbs0qqb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heading" /></template>
