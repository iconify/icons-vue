<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb45w1b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb45w1b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:book-open" /></template>
