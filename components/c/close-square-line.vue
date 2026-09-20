<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1gjvccpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1gjvccpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-square-line" /></template>
