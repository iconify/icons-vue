<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj00wcbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj00wcbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-right-fill" /></template>
