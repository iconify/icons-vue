<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_p8_75bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v_p8_75bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:image-search" /></template>
