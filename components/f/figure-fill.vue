<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzc1np7iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzc1np7iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figure-fill" /></template>
