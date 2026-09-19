<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksvj0z6ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="ksvj0z6ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:attachment" /></template>
