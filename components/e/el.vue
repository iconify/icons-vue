<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owbur9o1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owbur9o1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:el" /></template>
