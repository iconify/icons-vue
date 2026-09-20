<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxb14cb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qxb14cb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:asterisk-16" /></template>
