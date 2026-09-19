<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjn9d8bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272,"height":512};
const content = `<path class="kjn9d8bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:firebase-bolt" /></template>
