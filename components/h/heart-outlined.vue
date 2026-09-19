<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxqbb4wdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kxqbb4wdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:heart-outlined" /></template>
