<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idinelqba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idinelqba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-c-duocolor-round" /></template>
