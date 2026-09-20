<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuj-rabfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuj-rabfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:arrow-expand-flat" /></template>
