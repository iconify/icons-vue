<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1waho__y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1waho__y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v-waves-solid" /></template>
