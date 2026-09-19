<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze6oqhkxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ze6oqhkxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-bold-left" /></template>
