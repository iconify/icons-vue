<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkox7q6wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rkox7q6wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cas" /></template>
