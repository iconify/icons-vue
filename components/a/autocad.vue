<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrdmtsb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrdmtsb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:autocad" /></template>
