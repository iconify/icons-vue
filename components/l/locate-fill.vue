<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm3fv87sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm3fv87sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:locate-fill" /></template>
