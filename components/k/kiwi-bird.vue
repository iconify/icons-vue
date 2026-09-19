<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiox78u5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="tiox78u5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:kiwi-bird" /></template>
