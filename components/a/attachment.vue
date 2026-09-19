<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spvce6bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spvce6bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:attachment" /></template>
