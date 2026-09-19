<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-8pg3yxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m-8pg3yxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:autotask" /></template>
