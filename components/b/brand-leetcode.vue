<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqd1kacpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqd1kacpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-leetcode" /></template>
