<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4vbcacak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a4vbcacak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:glide-g" /></template>
