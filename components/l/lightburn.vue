<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l474j9beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l474j9beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lightburn" /></template>
