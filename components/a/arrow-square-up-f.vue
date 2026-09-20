<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0vjeccle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="a0vjeccle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-square-up-f" /></template>
