<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kha72tbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kha72tbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:instagramtwo" /></template>
