<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw3a_1zej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sw3a_1zej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:crown" /></template>
