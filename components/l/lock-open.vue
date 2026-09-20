<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-v8y7ptm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w-v8y7ptm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:lock-open" /></template>
