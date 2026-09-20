<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l59qypbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l59qypbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-book-fill" /></template>
