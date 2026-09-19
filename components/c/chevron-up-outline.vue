<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw1au2but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw1au2but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:chevron-up-outline" /></template>
