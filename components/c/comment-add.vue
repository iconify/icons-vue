<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk117eesu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lk117eesu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:comment-add" /></template>
