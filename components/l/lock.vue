<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrw_4kbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":32};
const content = `<path class="zrw_4kbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:lock" /></template>
