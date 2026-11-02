<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv0c1acyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv0c1acyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:checks-line" /></template>
