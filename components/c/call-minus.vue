<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyy1jn0kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyy1jn0kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-minus" /></template>
