<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnyugtbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnyugtbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-plus-round" /></template>
