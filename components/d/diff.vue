<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2l1q2ahw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2l1q2ahw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:diff" /></template>
