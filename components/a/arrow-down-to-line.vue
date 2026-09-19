<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik90xbc1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ik90xbc1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-to-line" /></template>
