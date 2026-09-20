<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk7jnxtbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vk7jnxtbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:adjust-hight-outline" /></template>
