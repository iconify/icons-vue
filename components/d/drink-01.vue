<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqf2av3eh.css';
import '../../css/f/fs-22ozdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqf2av3eh"/><path class="fs-22ozdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drink-01" /></template>
