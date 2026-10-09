<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeyvl7vpf.css';
import '../../css/w/wzh_nvbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yeyvl7vpf"/><path class="wzh_nvbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-tub-20" /></template>
