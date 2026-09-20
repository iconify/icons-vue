<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2nkza4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="ae2nkza4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:backward" /></template>
