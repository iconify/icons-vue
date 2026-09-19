<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksnpplbgb.css';
import '../../css/l/l6uihqb0x.css';
import '../../css/l/l5hse2boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ksnpplbgb"/><path class="l6uihqb0x"/><path class="l5hse2boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-view" /></template>
