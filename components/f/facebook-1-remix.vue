<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4eqsacgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w4eqsacgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:facebook-1-remix" /></template>
