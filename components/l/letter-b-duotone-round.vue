<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr17lu3bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr17lu3bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-b-duotone-round" /></template>
