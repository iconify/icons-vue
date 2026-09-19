<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpjvikbjg.css';
import '../../css/g/gleiq_5ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gpjvikbjg"/><path class="gleiq_5ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-kubernetes" /></template>
