<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ga9tbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3ga9tbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single-sharp" /></template>
