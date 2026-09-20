<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh827rbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh827rbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:badge-percent" /></template>
