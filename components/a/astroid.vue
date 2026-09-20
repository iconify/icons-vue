<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2jkixbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2jkixbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:astroid" /></template>
