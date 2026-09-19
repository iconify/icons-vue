<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb3iguelw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nb3iguelw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:divide-20-solid" /></template>
