<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8u1jgjki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8u1jgjki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-right-from-circle" /></template>
