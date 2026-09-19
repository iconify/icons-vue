<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvrxibcvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvrxibcvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:amaze-alt" /></template>
