<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjle34-cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjle34-cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-right-fill" /></template>
