<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjrfh32jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjrfh32jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:list-ordered-24" /></template>
