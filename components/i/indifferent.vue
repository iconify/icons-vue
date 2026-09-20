<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t794a8bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t794a8bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:indifferent" /></template>
