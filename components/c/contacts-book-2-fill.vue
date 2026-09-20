<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccq__ub1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccq__ub1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-book-2-fill" /></template>
