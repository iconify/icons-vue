<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3wqve3ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="c3wqve3ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-circle-up-right" /></template>
