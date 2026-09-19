<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjjd_7sue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1280};
const content = `<path class="pjjd_7sue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:inbox" /></template>
