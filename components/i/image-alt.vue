<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc__sdytk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jc__sdytk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:image-alt" /></template>
