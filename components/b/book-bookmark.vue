<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz_94093s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kz_94093s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book-bookmark" /></template>
