<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3x1ygbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3x1ygbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-fiverr" /></template>
