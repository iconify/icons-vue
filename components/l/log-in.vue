<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-uzbcchb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="a-uzbcchb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:log-in" /></template>
