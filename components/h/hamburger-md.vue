<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw36-dbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw36-dbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:hamburger-md" /></template>
