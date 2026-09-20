<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwr-_tbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwr-_tbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:home-minus" /></template>
