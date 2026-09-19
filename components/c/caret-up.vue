<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab5cd6g8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1280};
const content = `<path class="ab5cd6g8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:caret-up" /></template>
