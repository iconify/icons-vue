<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd0qzga6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd0qzga6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:image" /></template>
