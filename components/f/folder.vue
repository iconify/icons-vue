<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iltdvb4kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iltdvb4kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:folder" /></template>
