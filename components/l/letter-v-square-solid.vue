<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-9ht2b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-9ht2b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v-square-solid" /></template>
