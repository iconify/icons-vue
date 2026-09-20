<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5qfk5bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5qfk5bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:giphy" /></template>
