<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-6jceb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6jceb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:homepod-mini-fill" /></template>
