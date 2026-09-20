<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhpzrn5of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lhpzrn5of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grip-horizontal" /></template>
