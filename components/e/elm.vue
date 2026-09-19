<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faq4sdb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faq4sdb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:elm" /></template>
