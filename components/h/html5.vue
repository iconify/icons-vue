<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4zy16i2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4zy16i2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:html5" /></template>
