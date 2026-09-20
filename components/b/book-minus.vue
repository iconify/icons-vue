<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0rx2xbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0rx2xbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:book-minus" /></template>
