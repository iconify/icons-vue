<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6fpwyrhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o6fpwyrhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-right-circle" /></template>
