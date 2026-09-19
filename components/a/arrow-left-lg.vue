<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6gvj_2af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6gvj_2af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-left-lg" /></template>
